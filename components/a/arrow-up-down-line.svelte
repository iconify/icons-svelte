<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdw75iamg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdw75iamg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-down-line" {...props}></Icon>
