<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpqc5vbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpqc5vbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:money-bag-solid" {...props}></Icon>
