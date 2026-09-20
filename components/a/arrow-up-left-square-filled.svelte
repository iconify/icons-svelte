<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixisz2b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixisz2b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-left-square-filled" {...props}></Icon>
