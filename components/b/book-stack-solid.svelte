<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0x9u2gfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0x9u2gfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-stack-solid" {...props}></Icon>
