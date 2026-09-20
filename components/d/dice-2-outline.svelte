<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvmsos8ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvmsos8ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-2-outline" {...props}></Icon>
