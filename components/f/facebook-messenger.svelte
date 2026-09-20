<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzzo6jbar.css';
import '../../css/f/fnt2v3b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yzzo6jbar"/><path class="fnt2v3b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:facebook-messenger" {...props}></Icon>
