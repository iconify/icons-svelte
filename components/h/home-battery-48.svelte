<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0yys_sjp.css';
import '../../css/g/g3j-8gbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z0yys_sjp"/><path class="g3j-8gbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:home-battery-48" {...props}></Icon>
