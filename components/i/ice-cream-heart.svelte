<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb3iyoc2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb3iyoc2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ice-cream-heart" {...props}></Icon>
