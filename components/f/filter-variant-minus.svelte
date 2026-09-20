<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7rj7-bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7rj7-bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-variant-minus" {...props}></Icon>
