<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciq3bmhsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="ciq3bmhsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:quote-right" {...props}></Icon>
