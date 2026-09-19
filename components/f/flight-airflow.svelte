<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/f/f43rkvbca.css';
import '../../css/v/v31f7nbht.css';
import '../../css/h/hh9gxlbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="f43rkvbca"/><path class="v31f7nbht"/><path class="hh9gxlbei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:flight-airflow" {...props}></Icon>
