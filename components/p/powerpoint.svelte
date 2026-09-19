<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkgeb_bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bkgeb_bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:powerpoint" {...props}></Icon>
