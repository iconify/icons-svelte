<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1ix_v--p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u1ix_v--p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:handbag" {...props}></Icon>
