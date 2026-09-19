<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbgn4sy5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbgn4sy5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:grid-alt-filled" {...props}></Icon>
