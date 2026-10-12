<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnbt48bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xnbt48bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-fill-20" {...props}></Icon>
