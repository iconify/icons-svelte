<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yakfv4bol.css';
import '../../css/i/ivpk4lbsu.css';
import '../../css/h/hqe77eb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yakfv4bol"/><path class="ivpk4lbsu"/><path class="hqe77eb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:micro-hydro-20" {...props}></Icon>
