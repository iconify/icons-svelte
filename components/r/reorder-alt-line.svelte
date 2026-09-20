<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_-e5zbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_-e5zbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:reorder-alt-line" {...props}></Icon>
