<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn2kokbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="vn2kokbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:payu" {...props}></Icon>
