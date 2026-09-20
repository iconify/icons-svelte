<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nng69hcoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nng69hcoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:picture-in-picture-2-line" {...props}></Icon>
