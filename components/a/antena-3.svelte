<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_2qu44bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_2qu44bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:antena-3" {...props}></Icon>
