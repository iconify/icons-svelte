<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3co_8lgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3co_8lgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-move-left-x" {...props}></Icon>
