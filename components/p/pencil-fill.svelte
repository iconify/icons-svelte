<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d36krc8rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d36krc8rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pencil-fill" {...props}></Icon>
