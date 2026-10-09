<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlsjaz2ur.css';
import '../../css/m/mp2bmtb4q.css';
import '../../css/h/hfhgd-2kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jlsjaz2ur"/><path class="mp2bmtb4q"/><path class="hfhgd-2kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-cell-48-bold" {...props}></Icon>
