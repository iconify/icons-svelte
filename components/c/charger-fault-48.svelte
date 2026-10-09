<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnljhyiuk.css';
import '../../css/w/wxymvdbcb.css';
import '../../css/e/eeqb4o0lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fnljhyiuk"/><path class="wxymvdbcb"/><path class="eeqb4o0lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-fault-48" {...props}></Icon>
