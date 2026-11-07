<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lal7_isyr.css';
import '../../css/m/mjkr6tb4a.css';
import '../../css/w/wcny-ibdw.css';
import '../../css/x/x9024bb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lal7_isyr"/><path class="mjkr6tb4a"/><path class="wcny-ibdw"/><path clip-rule="evenodd" class="x9024bb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-code-outline" {...props}></Icon>
