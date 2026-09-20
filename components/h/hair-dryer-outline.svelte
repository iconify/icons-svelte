<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw9ii1w0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw9ii1w0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hair-dryer-outline" {...props}></Icon>
