<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oba2thrdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oba2thrdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:christmas-tree" {...props}></Icon>
