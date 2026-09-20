<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xig3ipb1f.css';
import '../../css/k/kh0mfynvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xig3ipb1f"/><path class="kh0mfynvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:envelopes-o" {...props}></Icon>
