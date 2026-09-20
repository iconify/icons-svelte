<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loq8_m6rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="loq8_m6rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-left-small-outline" {...props}></Icon>
