<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9gw86b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h9gw86b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:angularjs" {...props}></Icon>
