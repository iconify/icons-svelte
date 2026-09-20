<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpv_8_bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="vpv_8_bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bluetooth" {...props}></Icon>
