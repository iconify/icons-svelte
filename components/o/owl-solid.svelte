<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blkr1-zec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blkr1-zec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:owl-solid" {...props}></Icon>
