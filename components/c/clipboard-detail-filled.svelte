<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3q756b1j.css';
import '../../css/p/pd-a0f94r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3q756b1j"/><path class="pd-a0f94r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clipboard-detail-filled" {...props}></Icon>
