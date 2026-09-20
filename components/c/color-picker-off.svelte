<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndu43bc7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndu43bc7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:color-picker-off" {...props}></Icon>
