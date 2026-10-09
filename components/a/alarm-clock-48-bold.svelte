<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta5f1hbwd.css';
import '../../css/v/vgs6v8b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ta5f1hbwd"/><path class="vgs6v8b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alarm-clock-48-bold" {...props}></Icon>
