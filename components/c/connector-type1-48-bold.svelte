<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q668lybvz.css';
import '../../css/w/wxvvsl_vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q668lybvz"/><path class="wxvvsl_vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-type1-48-bold" {...props}></Icon>
