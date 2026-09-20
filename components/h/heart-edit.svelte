<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/h92865b4u.css';
import '../../css/r/ruoobvlrj.css';
import '../../css/p/p552hfbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h92865b4u"/><path class="ruoobvlrj"/><path class="p552hfbgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart-edit" {...props}></Icon>
