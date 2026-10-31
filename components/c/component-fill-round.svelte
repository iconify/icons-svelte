<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fph4z6l2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fph4z6l2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:component-fill-round" {...props}></Icon>
