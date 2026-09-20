<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkpun9bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kkpun9bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:prettier-16" {...props}></Icon>
