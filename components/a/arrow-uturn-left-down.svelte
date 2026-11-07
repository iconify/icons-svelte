<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjpgd0j_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjpgd0j_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-left-down" {...props}></Icon>
