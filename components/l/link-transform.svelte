<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckuydei1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckuydei1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:link-transform" {...props}></Icon>
