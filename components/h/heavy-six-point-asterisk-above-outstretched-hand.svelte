<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocf6zpbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ocf6zpbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heavy-six-point-asterisk-above-outstretched-hand" {...props}></Icon>
