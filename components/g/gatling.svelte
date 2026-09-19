<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sieu3cblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sieu3cblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gatling" {...props}></Icon>
