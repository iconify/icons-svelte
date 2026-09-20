<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g08_ym8px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g08_ym8px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-bold" {...props}></Icon>
