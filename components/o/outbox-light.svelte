<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf4qnrbtb.css';
import '../../css/v/vdot4tock.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf4qnrbtb"/><path class="vdot4tock"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:outbox-light" {...props}></Icon>
