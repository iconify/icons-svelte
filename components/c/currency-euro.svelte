<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbmwvhb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hbmwvhb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:currency-euro" {...props}></Icon>
