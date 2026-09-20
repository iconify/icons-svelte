<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggm8cpb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggm8cpb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:heroic-games-launcher" {...props}></Icon>
