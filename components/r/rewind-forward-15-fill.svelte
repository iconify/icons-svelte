<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ackwvkend.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ackwvkend"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-15-fill" {...props}></Icon>
