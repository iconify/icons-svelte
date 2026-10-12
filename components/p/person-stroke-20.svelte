<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws1d6xdgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ws1d6xdgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-stroke-20" {...props}></Icon>
