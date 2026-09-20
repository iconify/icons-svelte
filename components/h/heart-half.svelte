<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzqyp-d2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzqyp-d2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:heart-half" {...props}></Icon>
