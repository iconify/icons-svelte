<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyn89ysya.css';
import '../../css/u/usuy8n_ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uyn89ysya"/><path class="usuy8n_ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-top-20" {...props}></Icon>
