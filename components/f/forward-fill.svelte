<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiz4bsboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oiz4bsboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:forward-fill" {...props}></Icon>
