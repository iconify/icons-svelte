<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpuha0xak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpuha0xak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:code-slash" {...props}></Icon>
