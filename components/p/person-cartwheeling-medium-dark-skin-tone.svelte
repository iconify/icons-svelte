<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf5b9zb0i.css';
import '../../css/h/hhvthyu9m.css';
import '../../css/m/mi4jrix-s.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/c/cgxswbbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="vf5b9zb0i"><circle class="hhvthyu9m"/><path class="mi4jrix-s"/></g><g class="x8poo_bjf"><circle class="hhvthyu9m"/><path class="cgxswbbyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:person-cartwheeling-medium-dark-skin-tone" {...props}></Icon>
