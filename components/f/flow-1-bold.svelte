<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foz0jfb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foz0jfb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flow-1-bold" {...props}></Icon>
