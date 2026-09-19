<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s92d9qb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s92d9qb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:heat-map-03" {...props}></Icon>
