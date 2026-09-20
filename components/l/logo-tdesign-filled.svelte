<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpa83o-uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpa83o-uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-tdesign-filled" {...props}></Icon>
