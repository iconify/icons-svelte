<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzkqj_b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzkqj_b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:audio-wave-02" {...props}></Icon>
