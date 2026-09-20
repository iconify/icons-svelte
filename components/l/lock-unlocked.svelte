<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv99bxbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv99bxbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:lock-unlocked" {...props}></Icon>
