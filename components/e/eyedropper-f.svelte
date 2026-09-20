<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gry-cbbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="gry-cbbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:eyedropper-f" {...props}></Icon>
