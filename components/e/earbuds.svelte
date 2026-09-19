<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm0rkj2aq.css';
import '../../css/s/sjyb2qfru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm0rkj2aq"/><path class="sjyb2qfru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:earbuds" {...props}></Icon>
