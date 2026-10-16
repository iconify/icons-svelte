<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijnfvxjhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ijnfvxjhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earbuds-48" {...props}></Icon>
