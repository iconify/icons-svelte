<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjpi7urvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjpi7urvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bag-alt" {...props}></Icon>
