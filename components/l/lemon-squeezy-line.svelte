<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc013ab-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc013ab-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lemon-squeezy-line" {...props}></Icon>
