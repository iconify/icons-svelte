<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht1an5bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht1an5bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:arrow-down" {...props}></Icon>
