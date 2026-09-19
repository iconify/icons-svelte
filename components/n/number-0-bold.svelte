<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixsi4-b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixsi4-b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-0-bold" {...props}></Icon>
