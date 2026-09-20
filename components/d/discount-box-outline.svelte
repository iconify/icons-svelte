<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqk6_dbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqk6_dbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:discount-box-outline" {...props}></Icon>
