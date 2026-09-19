<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e61bgw5xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e61bgw5xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:hash-outline" {...props}></Icon>
