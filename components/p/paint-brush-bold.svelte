<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzofximaw.css';
import '../../css/k/kbosvfeuz.css';
import '../../css/x/xkwuocbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzofximaw"/><path class="kbosvfeuz"/><path class="xkwuocbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paint-brush-bold" {...props}></Icon>
