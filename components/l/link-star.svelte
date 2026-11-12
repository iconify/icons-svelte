<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkt-o0bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkt-o0bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-star" {...props}></Icon>
