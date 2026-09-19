<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/msz60p3bx.css';
import '../../css/m/mp63jovjl.css';
import '../../css/k/kgmv5bb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="msz60p3bx"/><circle class="mp63jovjl"/><path class="kgmv5bb8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:gauze" {...props}></Icon>
