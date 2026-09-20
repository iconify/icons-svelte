<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mx0ewsb4i.css';
import '../../css/t/t94t6tb6s.css';
import '../../css/r/rxtnv1b8t.css';
import '../../css/j/jcuabtghe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="mx0ewsb4i"/><path class="t94t6tb6s"/><path class="rxtnv1b8t"/><path class="jcuabtghe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cam-web-light" {...props}></Icon>
