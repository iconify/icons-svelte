<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdp3c-zxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdp3c-zxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart2-filled" {...props}></Icon>
