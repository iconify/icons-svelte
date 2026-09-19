<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0mfz3j4c.css';
import '../../css/u/uvedyyb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0mfz3j4c"/><path class="uvedyyb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-group" {...props}></Icon>
