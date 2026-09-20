<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9uy85bkb.css';
import '../../css/h/hw50cc_wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9uy85bkb"/><path class="hw50cc_wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:mailbox-full-light" {...props}></Icon>
