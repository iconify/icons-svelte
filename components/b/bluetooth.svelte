<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vobx5xbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vobx5xbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bluetooth" {...props}></Icon>
