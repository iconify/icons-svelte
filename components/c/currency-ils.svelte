<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2b9dkbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2b9dkbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-ils" {...props}></Icon>
