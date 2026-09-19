<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r046gcc4f.css';
import '../../css/f/f7m0-ntgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b r046gcc4f"/><path class="b f7m0-ntgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gradient" {...props}></Icon>
