<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrr_t1bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrr_t1bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bank" {...props}></Icon>
