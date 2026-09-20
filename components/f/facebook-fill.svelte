<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ava2r5bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ava2r5bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:facebook-fill" {...props}></Icon>
