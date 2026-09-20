<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkftz_bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkftz_bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:focus-auto-1" {...props}></Icon>
