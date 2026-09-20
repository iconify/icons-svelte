<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz-efebcs.css';
import '../../css/n/n2j-lhblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-efebcs"/><path class="n2j-lhblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:explicit-content" {...props}></Icon>
