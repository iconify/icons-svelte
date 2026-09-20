<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4ih2k-9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4ih2k-9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-wireless-off" {...props}></Icon>
