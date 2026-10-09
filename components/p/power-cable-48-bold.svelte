<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfbb1fbyd.css';
import '../../css/h/h4_86xb7u.css';
import '../../css/o/o8n6aqd3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kfbb1fbyd"/><path class="h4_86xb7u"/><path class="o8n6aqd3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-cable-48-bold" {...props}></Icon>
