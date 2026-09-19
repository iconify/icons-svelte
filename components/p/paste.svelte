<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cobfg59dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cobfg59dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:paste" {...props}></Icon>
