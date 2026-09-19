<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph1egc8-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ph1egc8-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bucket-fill" {...props}></Icon>
