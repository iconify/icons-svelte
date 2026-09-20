<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx1qtac8g.css';
import '../../css/w/wkho5gbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx1qtac8g"/><path class="wkho5gbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:mailbox-empty-duotone" {...props}></Icon>
