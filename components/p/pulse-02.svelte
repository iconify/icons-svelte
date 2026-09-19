<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cld4rmjox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cld4rmjox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pulse-02" {...props}></Icon>
