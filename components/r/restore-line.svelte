<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmq9d11ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmq9d11ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:restore-line" {...props}></Icon>
