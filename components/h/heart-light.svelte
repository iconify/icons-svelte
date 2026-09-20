<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd47nrbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd47nrbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:heart-light" {...props}></Icon>
