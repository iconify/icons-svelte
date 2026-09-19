<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xunp2ibkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xunp2ibkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:edit-3" {...props}></Icon>
