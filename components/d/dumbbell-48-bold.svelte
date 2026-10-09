<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl8r3viay.css';
import '../../css/q/qdpkq-bcf.css';
import '../../css/l/l89fhnblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vl8r3viay"/><path class="qdpkq-bcf"/><path class="l89fhnblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dumbbell-48-bold" {...props}></Icon>
