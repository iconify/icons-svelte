<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz7r0yydl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz7r0yydl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pill-bottle-check" {...props}></Icon>
