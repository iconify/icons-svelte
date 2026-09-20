<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt2s5wknr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zt2s5wknr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:play-stream" {...props}></Icon>
