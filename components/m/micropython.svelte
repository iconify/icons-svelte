<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/der6foqae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="der6foqae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:micropython" {...props}></Icon>
