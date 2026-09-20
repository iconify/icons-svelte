<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq8b29b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq8b29b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:following" {...props}></Icon>
