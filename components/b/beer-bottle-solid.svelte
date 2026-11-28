<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hot8poxda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hot8poxda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:beer-bottle-solid" {...props}></Icon>
