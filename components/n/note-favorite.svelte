<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/vfl_-cgfn.css';
import '../../css/b/btnov_7jm.css';
import '../../css/x/xcwbr8b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vfl_-cgfn"/><path class="btnov_7jm"/><path class="xcwbr8b4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:note-favorite" {...props}></Icon>
