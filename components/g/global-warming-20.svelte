<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l80gl972s.css';
import '../../css/q/qyw8labld.css';
import '../../css/j/jo8s-ccbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l80gl972s"/><path class="qyw8labld"/><path class="jo8s-ccbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:global-warming-20" {...props}></Icon>
