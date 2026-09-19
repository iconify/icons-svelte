<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-e-4ab9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-e-4ab9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bookmark-alt-minus" {...props}></Icon>
