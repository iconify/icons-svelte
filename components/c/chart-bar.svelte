<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecsrbub4u.css';
import '../../css/m/mnlk1ccyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ecsrbub4u"/><path class="mnlk1ccyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:chart-bar" {...props}></Icon>
