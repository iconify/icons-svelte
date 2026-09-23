<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4qanbbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4qanbbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chess-knight" {...props}></Icon>
