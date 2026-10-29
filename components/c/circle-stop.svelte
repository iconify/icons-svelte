<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q97ltfs3e.css';
import '../../css/b/bwzdesbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q97ltfs3e wm-k"/><path class="bwzdesbyr wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:circle-stop" {...props}></Icon>
