<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt_r8ccrc.css';
import '../../css/t/tdc8sp8bz.css';
import '../../css/n/nkkhqzxyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt_r8ccrc"/><path class="tdc8sp8bz"/><path class="nkkhqzxyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-route-planning-filled" {...props}></Icon>
