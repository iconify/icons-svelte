<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6d91yjnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6d91yjnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-certificate-outline" {...props}></Icon>
