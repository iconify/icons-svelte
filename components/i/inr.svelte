<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9xnn3bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="g9xnn3bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:inr" {...props}></Icon>
