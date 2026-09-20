<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz-efebcs.css';
import '../../css/m/mlbjv-b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-efebcs"/><path class="mlbjv-b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:explicit-content-duotone" {...props}></Icon>
