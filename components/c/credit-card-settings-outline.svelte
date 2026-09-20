<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikf92o_9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikf92o_9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-settings-outline" {...props}></Icon>
