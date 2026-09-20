<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ape3adbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ape3adbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:grunt" {...props}></Icon>
