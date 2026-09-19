<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjl1aubud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjl1aubud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-donate-blood" {...props}></Icon>
