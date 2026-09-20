<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frms94-ux.css';
import '../../css/h/haeexlbuc.css';
import '../../css/u/ubiksac-u.css';
import '../../css/e/eyimmqbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="frms94-ux"><path class="haeexlbuc"/><path class="ubiksac-u"/><path class="eyimmqbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:redux-reducer" {...props}></Icon>
