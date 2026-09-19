<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6_fg-lkg.css';
import '../../css/k/kpu7t4bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6_fg-lkg"/><path class="kpu7t4bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-right-stroke-circle" {...props}></Icon>
