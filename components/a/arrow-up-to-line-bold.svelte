<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqe-1p3yw.css';
import '../../css/o/ohna_rbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqe-1p3yw"/><path class="ohna_rbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-to-line-bold" {...props}></Icon>
