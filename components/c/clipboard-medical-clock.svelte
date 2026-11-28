<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kocx10j0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kocx10j0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-medical-clock" {...props}></Icon>
