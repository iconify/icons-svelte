<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi4tymrtz.css';
import '../../css/k/k51gsefpd.css';
import '../../css/u/u1wdaq6xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi4tymrtz"/><path clip-rule="evenodd" class="k51gsefpd"/><path clip-rule="evenodd" class="u1wdaq6xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:emoji-joy-light" {...props}></Icon>
