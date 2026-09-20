<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2ljbc5we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2ljbc5we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gallery3" {...props}></Icon>
