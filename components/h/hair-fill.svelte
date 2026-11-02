<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sda08wk8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sda08wk8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hair-fill" {...props}></Icon>
