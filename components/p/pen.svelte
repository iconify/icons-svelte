<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d59qz9bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d59qz9bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:pen" {...props}></Icon>
