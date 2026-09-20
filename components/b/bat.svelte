<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqu-4rbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqu-4rbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bat" {...props}></Icon>
