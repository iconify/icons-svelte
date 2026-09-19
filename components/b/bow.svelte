<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzoi8ll2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kzoi8ll2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bow" {...props}></Icon>
