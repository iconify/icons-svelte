<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-wvqqbgn.css';
import '../../css/u/usv0f7brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-wvqqbgn"/><path clip-rule="evenodd" class="usv0f7brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:flask-alt-outline" {...props}></Icon>
