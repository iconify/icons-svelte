<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljagxxz5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljagxxz5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fingerprint-1" {...props}></Icon>
