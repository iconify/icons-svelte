<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvcz6hbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcz6hbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:burger-alt-filled" {...props}></Icon>
