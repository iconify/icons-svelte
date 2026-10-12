<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt8fudb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bt8fudb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cube-stroke-20" {...props}></Icon>
