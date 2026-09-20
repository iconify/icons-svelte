<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vybyybb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vybyybb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-down-up-20-solid" {...props}></Icon>
