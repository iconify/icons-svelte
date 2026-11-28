<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gei0--jlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gei0--jlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:filter" {...props}></Icon>
