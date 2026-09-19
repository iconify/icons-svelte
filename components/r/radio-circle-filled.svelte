<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8w03vp9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8w03vp9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:radio-circle-filled" {...props}></Icon>
