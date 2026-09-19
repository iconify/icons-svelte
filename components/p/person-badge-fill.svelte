<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0ku27byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d0ku27byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-badge-fill" {...props}></Icon>
