<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8i2mt98p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w8i2mt98p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pause-circle-bold" {...props}></Icon>
