<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcc74ebsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcc74ebsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bolt-linear" {...props}></Icon>
