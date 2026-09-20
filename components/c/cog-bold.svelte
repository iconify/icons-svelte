<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1ggjibbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ggjibbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cog-bold" {...props}></Icon>
