<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4uy2hbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4uy2hbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pill-plus" {...props}></Icon>
