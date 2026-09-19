<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojhmxp_8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ojhmxp_8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:r-project" {...props}></Icon>
