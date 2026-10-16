<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz333ohex.css';
import '../../css/t/tavztwb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mz333ohex"/><path class="tavztwb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:respirator-20" {...props}></Icon>
