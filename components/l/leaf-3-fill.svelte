<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue9d2bbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue9d2bbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-3-fill" {...props}></Icon>
