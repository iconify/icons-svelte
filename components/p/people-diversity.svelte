<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t89--hbtm.css';
import '../../css/s/sbh-k_brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t89--hbtm"/><path class="sbh-k_brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:people-diversity" {...props}></Icon>
