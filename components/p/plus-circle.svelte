<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml8jy-bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml8jy-bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:plus-circle" {...props}></Icon>
