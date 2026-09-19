<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kex8uib9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="kex8uib9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nav-icon" {...props}></Icon>
