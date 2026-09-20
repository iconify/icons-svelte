<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odqejdbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odqejdbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-seven-box" {...props}></Icon>
