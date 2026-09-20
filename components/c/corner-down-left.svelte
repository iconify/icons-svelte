<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk752qipy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk752qipy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:corner-down-left" {...props}></Icon>
