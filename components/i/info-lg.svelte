<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqt0chb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oqt0chb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:info-lg" {...props}></Icon>
