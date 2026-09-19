<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjhzgobae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjhzgobae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:inbox" {...props}></Icon>
