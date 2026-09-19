<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cosbr_2hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cosbr_2hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lock-off-fill" {...props}></Icon>
