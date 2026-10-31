<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqvyfqbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqvyfqbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fox-round" {...props}></Icon>
