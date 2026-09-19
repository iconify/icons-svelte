<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngef1bydj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngef1bydj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pulse-01" {...props}></Icon>
