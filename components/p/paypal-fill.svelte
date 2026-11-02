<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5qbncc5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5qbncc5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paypal-fill" {...props}></Icon>
