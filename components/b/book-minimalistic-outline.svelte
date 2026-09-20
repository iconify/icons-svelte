<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iep4jyacq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iep4jyacq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:book-minimalistic-outline" {...props}></Icon>
