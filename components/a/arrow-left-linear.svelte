<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn2j1eees.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn2j1eees"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-linear" {...props}></Icon>
