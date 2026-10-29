<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szzww6bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szzww6bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:blocks" {...props}></Icon>
