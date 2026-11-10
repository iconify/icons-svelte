<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqf4-fbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqf4-fbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:iota" {...props}></Icon>
