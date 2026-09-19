<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/g/ggi3ly9zi.css';
import '../../css/j/jzc552pxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="ggi3ly9zi"/><path class="jzc552pxa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:api-app" {...props}></Icon>
