<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqz4vgzgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqz4vgzgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-down-left-linear" {...props}></Icon>
