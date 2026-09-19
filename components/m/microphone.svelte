<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2fb49ins.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2fb49ins"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:microphone" {...props}></Icon>
