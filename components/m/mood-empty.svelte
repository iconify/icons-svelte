<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c26-vcbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c26-vcbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-empty" {...props}></Icon>
