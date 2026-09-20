<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak2bjr-cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak2bjr-cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-5-1" {...props}></Icon>
