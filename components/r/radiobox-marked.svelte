<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx7n_hboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx7n_hboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radiobox-marked" {...props}></Icon>
