<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn8qimbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn8qimbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-plus-fill-round" {...props}></Icon>
