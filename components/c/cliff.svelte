<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4seh8bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s4seh8bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cliff" {...props}></Icon>
