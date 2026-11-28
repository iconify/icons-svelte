<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz2v2pcnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz2v2pcnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cassette-solid" {...props}></Icon>
