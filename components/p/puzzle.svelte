<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he3c9zg2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="he3c9zg2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:puzzle" {...props}></Icon>
