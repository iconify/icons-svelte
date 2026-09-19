<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbw5dkbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbw5dkbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:bluetooth-bold" {...props}></Icon>
