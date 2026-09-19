<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq777ab-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oq777ab-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:hour-glass" {...props}></Icon>
