<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcj8ggbve.css';
import '../../css/a/aynzu-bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":222,"height":217};
const content = `<path class="zcj8ggbve"/><path class="aynzu-bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:justcall" {...props}></Icon>
