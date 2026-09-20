<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/houoq25gr.css';
import '../../css/i/iidgtubnu.css';
import '../../css/s/su0illb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="houoq25gr"/><path class="iidgtubnu"/><path class="su0illb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:cloud-upload" {...props}></Icon>
