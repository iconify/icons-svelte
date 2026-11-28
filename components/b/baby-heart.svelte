<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3x45efmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3x45efmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:baby-heart" {...props}></Icon>
