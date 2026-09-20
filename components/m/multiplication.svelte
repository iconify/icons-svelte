<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzf3jntxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzf3jntxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:multiplication" {...props}></Icon>
