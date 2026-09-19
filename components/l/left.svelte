<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtfmx7b3v.css';
import '../../css/b/bopf4ubik.css';
import '../../css/e/eb6s51zoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wtfmx7b3v"><path class="bopf4ubik"/><path class="eb6s51zoz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:left" {...props}></Icon>
