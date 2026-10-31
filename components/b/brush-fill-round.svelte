<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhzi21-9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhzi21-9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brush-fill-round" {...props}></Icon>
