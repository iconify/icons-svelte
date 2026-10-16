<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbc6c5bqk.css';
import '../../css/x/xy_8owk3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nbc6c5bqk"/><path class="xy_8owk3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-joint-48" {...props}></Icon>
