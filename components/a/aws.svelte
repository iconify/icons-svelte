<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm0vp1ieb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm0vp1ieb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:aws" {...props}></Icon>
