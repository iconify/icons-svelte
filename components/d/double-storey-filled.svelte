<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdtr-tgcy.css';
import '../../css/x/xqehzub3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdtr-tgcy"/><path class="xqehzub3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:double-storey-filled" {...props}></Icon>
