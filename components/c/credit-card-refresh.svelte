<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-_rn-v-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-_rn-v-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-refresh" {...props}></Icon>
