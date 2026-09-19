<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suf1grbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suf1grbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:info-octagon-filled" {...props}></Icon>
