<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuylt021t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuylt021t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-info-round" {...props}></Icon>
