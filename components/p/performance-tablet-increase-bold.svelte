<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgdd18btl.css';
import '../../css/y/y2ci2rbgk.css';
import '../../css/p/pkw90xu3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgdd18btl"/><path class="y2ci2rbgk"/><path class="pkw90xu3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:performance-tablet-increase-bold" {...props}></Icon>
