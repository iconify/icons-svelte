<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rarvwdbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rarvwdbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-cloud-solid" {...props}></Icon>
