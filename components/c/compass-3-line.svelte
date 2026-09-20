<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz2qd0bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz2qd0bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:compass-3-line" {...props}></Icon>
