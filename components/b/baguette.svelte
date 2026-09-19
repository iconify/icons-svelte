<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-otfqkuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-otfqkuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:baguette" {...props}></Icon>
