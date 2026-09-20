<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nffkq2bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nffkq2bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-tencentmeeting-filled" {...props}></Icon>
