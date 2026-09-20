<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kli4i-b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kli4i-b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fahrenheit-scale" {...props}></Icon>
