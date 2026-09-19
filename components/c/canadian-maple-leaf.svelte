<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owv2r90mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="owv2r90mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:canadian-maple-leaf" {...props}></Icon>
