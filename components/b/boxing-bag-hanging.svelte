<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwpspbb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwpspbb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:boxing-bag-hanging" {...props}></Icon>
