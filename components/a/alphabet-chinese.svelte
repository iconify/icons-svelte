<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_0kzp__o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_0kzp__o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:alphabet-chinese" {...props}></Icon>
