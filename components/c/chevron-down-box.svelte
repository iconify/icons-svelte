<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eym5mrbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eym5mrbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-down-box" {...props}></Icon>
