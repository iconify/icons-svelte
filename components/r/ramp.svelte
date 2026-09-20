<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szy26opxx.css';
import '../../css/c/csou2mbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szy26opxx"/><path class="csou2mbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ramp" {...props}></Icon>
