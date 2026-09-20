<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef904ebom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef904ebom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:logout-box-r-line" {...props}></Icon>
