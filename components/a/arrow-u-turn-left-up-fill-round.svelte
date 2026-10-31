<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anh4j2bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anh4j2bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-left-up-fill-round" {...props}></Icon>
