<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm9sh3z2f.css';
import '../../css/j/j319albkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xm9sh3z2f"/><path class="j319albkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:microphone-stroke-20" {...props}></Icon>
