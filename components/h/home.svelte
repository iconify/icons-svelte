<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxnw4-snz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxnw4-snz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:home" {...props}></Icon>
