<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou-cxiblp.css';
import '../../css/j/jheawubao.css';
import '../../css/h/h1a11qb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ou-cxiblp"/><path class="jheawubao"/><path class="h1a11qb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-valve-48" {...props}></Icon>
