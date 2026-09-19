<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7_amibcp.css';
import '../../css/w/wob-_umgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7_amibcp"/><path class="wob-_umgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-json" {...props}></Icon>
