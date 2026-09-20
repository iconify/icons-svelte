<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu-u_113z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eu-u_113z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x3-20-solid" {...props}></Icon>
