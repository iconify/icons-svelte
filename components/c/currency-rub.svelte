<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e25chh61c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e25chh61c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-rub" {...props}></Icon>
