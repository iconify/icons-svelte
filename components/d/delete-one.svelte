<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/g1-qxqbur.css';
import '../../css/j/jgg56cbfn.css';
import '../../css/v/vxzaw_bgf.css';
import '../../css/d/dml3zeblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="g1-qxqbur"/><path class="jgg56cbfn"/><path clip-rule="evenodd" class="vxzaw_bgf"/><path class="dml3zeblg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:delete-one" {...props}></Icon>
