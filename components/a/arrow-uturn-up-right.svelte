<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb4x6yu9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xb4x6yu9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-uturn-up-right" {...props}></Icon>
