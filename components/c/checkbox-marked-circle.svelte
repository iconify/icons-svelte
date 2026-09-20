<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rose2n_gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rose2n_gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-marked-circle" {...props}></Icon>
