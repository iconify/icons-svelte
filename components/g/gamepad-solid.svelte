<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q32wvdbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q32wvdbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:gamepad-solid" {...props}></Icon>
