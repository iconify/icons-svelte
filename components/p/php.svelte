<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwv858cch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwv858cch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:php" {...props}></Icon>
