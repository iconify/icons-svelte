<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8mocyz2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f8mocyz2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gitter" {...props}></Icon>
