<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu1k2-bmq.css';
import '../../css/p/pa14hnb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu1k2-bmq"/><path class="pa14hnb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clipboard-code" {...props}></Icon>
