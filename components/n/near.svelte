<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu1cjp9dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu1cjp9dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:near" {...props}></Icon>
