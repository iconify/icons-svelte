<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hltfq1i2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hltfq1i2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:log-out" {...props}></Icon>
