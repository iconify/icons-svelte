<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vomlb2-jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vomlb2-jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:check" {...props}></Icon>
