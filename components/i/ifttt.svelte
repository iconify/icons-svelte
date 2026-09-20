<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7bt9bcab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7bt9bcab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ifttt" {...props}></Icon>
