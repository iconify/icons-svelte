<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi7c6csqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi7c6csqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-yen-off" {...props}></Icon>
