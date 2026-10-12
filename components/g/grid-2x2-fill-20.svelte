<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq3mh2agg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eq3mh2agg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-2x2-fill-20" {...props}></Icon>
