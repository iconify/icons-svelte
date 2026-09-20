<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsf_iqb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsf_iqb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:poker-diamonds-line" {...props}></Icon>
