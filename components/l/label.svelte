<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eefxmpbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eefxmpbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:label" {...props}></Icon>
