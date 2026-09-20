<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djp2kgbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djp2kgbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:amusement-park-electric-cars" {...props}></Icon>
