<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnosz2bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnosz2bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dental-tooth" {...props}></Icon>
