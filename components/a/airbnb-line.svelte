<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ousbncbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ousbncbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airbnb-line" {...props}></Icon>
