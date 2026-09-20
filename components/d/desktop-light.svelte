<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8kn_3bny.css';
import '../../css/f/fn8q6tmlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8kn_3bny"/><path class="fn8q6tmlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:desktop-light" {...props}></Icon>
