<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdaa5te7j.css';
import '../../css/j/jtlbg74id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wdaa5te7j"/><path class="jtlbg74id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:at-sign-48-bold" {...props}></Icon>
