<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyybk_84w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyybk_84w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-down-right" {...props}></Icon>
