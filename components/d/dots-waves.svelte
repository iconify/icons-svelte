<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ti2c57j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ti2c57j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-waves" {...props}></Icon>
