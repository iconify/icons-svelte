<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0v50k2an.css';
import '../../css/x/xwaa6bbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t0v50k2an"/><path class="xwaa6bbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-lock-48-bold" {...props}></Icon>
