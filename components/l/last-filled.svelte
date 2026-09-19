<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc-h5mb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc-h5mb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:last-filled" {...props}></Icon>
