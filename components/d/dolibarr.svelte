<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct8vf37rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct8vf37rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dolibarr" {...props}></Icon>
