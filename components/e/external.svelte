<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0rveybpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0rveybpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:external" {...props}></Icon>
