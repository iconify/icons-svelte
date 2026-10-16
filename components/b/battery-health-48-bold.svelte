<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns5zs0vev.css';
import '../../css/q/qdjmx6jro.css';
import '../../css/y/yaab6pb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ns5zs0vev"/><path class="qdjmx6jro"/><path class="yaab6pb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-health-48-bold" {...props}></Icon>
