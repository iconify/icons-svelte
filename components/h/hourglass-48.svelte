<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbfsj092o.css';
import '../../css/j/jc99_77ng.css';
import '../../css/n/n994qc39b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kbfsj092o"/><path class="jc99_77ng"/><path class="n994qc39b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hourglass-48" {...props}></Icon>
