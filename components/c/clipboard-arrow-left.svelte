<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbn6v21yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbn6v21yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-arrow-left" {...props}></Icon>
