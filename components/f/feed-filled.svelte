<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg0rntbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bg0rntbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:feed-filled" {...props}></Icon>
