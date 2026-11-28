<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exw2fxbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exw2fxbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-open-sparkles-solid" {...props}></Icon>
