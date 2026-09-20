<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txc5-tbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txc5-tbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cog-transfer" {...props}></Icon>
