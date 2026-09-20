<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4yvqi4xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4yvqi4xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dc" {...props}></Icon>
