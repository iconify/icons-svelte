<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg-sms8br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wg-sms8br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffee-mug-and-wifi" {...props}></Icon>
