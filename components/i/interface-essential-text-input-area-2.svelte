<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptpts-iao.css';
import '../../css/k/kjhhmyhjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ptpts-iao"/><path class="kjhhmyhjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-text-input-area-2" {...props}></Icon>
