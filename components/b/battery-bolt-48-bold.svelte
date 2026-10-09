<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-0u49zj.css';
import '../../css/w/wh24nx91b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ok-0u49zj"/><path class="wh24nx91b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-bolt-48-bold" {...props}></Icon>
