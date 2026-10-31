<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1j0rrb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1j0rrb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-minus-round" {...props}></Icon>
