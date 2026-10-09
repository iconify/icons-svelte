<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-q4zlgza.css';
import '../../css/g/g6-ekr0nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a-q4zlgza"/><path class="g6-ekr0nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:conveyor-48" {...props}></Icon>
