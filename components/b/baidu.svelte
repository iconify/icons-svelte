<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1ll4_eeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c1ll4_eeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:baidu" {...props}></Icon>
