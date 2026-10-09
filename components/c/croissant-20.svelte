<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdfc7kbln.css';
import '../../css/p/plyl_b4bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gdfc7kbln"/><path class="plyl_b4bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:croissant-20" {...props}></Icon>
