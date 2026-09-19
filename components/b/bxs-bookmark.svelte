<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8-d1ab8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8-d1ab8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bookmark" {...props}></Icon>
