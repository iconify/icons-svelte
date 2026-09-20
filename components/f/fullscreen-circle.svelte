<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4q6x8k5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4q6x8k5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fullscreen-circle" {...props}></Icon>
