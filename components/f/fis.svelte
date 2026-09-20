<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz9tmwbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz9tmwbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fis" {...props}></Icon>
