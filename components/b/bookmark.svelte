<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu7zv7b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu7zv7b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:bookmark" {...props}></Icon>
