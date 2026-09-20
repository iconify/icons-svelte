<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7x1nnbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7x1nnbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-play-line" {...props}></Icon>
