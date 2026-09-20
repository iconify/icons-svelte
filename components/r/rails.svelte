<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k__ujmbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k__ujmbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:rails" {...props}></Icon>
