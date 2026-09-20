<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jerixg-mq.css';
import '../../css/x/x-sfqoban.css';
import '../../css/d/d46zpdbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jerixg-mq"/><path class="x-sfqoban"/><path class="d46zpdbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-defender-dark" {...props}></Icon>
