<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrij_qbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrij_qbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-multiple-remove" {...props}></Icon>
