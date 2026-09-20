<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxd3y1b3a.css';
import '../../css/r/rtb6i2lma.css';
import '../../css/i/i6hc7lykz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxd3y1b3a"/><path class="rtb6i2lma"/><path class="i6hc7lykz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bzr" {...props}></Icon>
