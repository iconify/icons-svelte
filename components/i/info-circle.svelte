<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xud0d_adg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xud0d_adg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:info-circle" {...props}></Icon>
