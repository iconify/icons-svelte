<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inr7twbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inr7twbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:copper-coin-line" {...props}></Icon>
