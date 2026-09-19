<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxmcy1bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxmcy1bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fire-alt-filled" {...props}></Icon>
