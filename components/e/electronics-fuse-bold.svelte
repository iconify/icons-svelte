<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6hq5bt1d.css';
import '../../css/m/m-9tadk8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6hq5bt1d"/><path class="m-9tadk8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:electronics-fuse-bold" {...props}></Icon>
