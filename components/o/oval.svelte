<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx6syuhyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx6syuhyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:oval" {...props}></Icon>
