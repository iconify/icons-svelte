<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq0w_mbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="kq0w_mbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:calculator" {...props}></Icon>
