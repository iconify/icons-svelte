<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jblxonclo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jblxonclo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-square-15-fill" {...props}></Icon>
