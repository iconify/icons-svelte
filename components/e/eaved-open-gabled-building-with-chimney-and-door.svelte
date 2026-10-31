<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9bvnqb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q9bvnqb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-open-gabled-building-with-chimney-and-door" {...props}></Icon>
