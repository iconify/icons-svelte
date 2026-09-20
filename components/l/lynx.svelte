<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmq9vpghv.css';
import '../../css/t/twk1xgb_t.css';
import '../../css/t/t6s89ibas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dmq9vpghv"><path clip-rule="evenodd" class="twk1xgb_t"/><path class="t6s89ibas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lynx" {...props}></Icon>
