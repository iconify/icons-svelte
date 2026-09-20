<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f45raequf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f45raequf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:roadster-fill" {...props}></Icon>
