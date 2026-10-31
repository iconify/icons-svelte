<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwpr0gbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwpr0gbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:npm-fill-round" {...props}></Icon>
