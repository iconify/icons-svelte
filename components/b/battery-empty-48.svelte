<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s84xoibnh.css';
import '../../css/d/dbhsu82qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s84xoibnh"/><path class="dbhsu82qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-empty-48" {...props}></Icon>
