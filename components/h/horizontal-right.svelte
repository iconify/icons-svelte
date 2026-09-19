<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqc49ei0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqc49ei0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:horizontal-right" {...props}></Icon>
