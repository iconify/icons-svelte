<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxg65syqu.css';
import '../../css/b/b0dccwb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxg65syqu"/><path class="b0dccwb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:channel-filled" {...props}></Icon>
