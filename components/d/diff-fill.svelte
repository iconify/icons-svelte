<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mptdx2ore.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mptdx2ore"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diff-fill" {...props}></Icon>
