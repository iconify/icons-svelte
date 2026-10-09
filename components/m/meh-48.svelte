<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hac57wbhi.css';
import '../../css/w/ws03jtgtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="ws03jtgtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:meh-48" {...props}></Icon>
