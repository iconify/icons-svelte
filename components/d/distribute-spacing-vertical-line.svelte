<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvb3wvk0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvb3wvk0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:distribute-spacing-vertical-line" {...props}></Icon>
