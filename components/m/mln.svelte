<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e4gndac2i.css';
import '../../css/m/mr0kfgbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="e4gndac2i"/><path class="mr0kfgbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:mln" {...props}></Icon>
