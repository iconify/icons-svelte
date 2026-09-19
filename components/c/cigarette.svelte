<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8bbgrb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8bbgrb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cigarette" {...props}></Icon>
