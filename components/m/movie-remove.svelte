<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bld70-bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bld70-bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-remove" {...props}></Icon>
