<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmuwlogjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmuwlogjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:flag-plus" {...props}></Icon>
