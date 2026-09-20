<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o244-4_zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o244-4_zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:history3-filled" {...props}></Icon>
