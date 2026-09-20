<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frj64eb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="frj64eb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-outlook-2018-light" {...props}></Icon>
