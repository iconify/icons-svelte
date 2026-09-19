<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2dqbpl9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g2dqbpl9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-outline" {...props}></Icon>
