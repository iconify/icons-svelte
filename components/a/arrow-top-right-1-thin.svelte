<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjt-f13vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjt-f13vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-right-1-thin" {...props}></Icon>
