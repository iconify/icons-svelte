<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh-317bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh-317bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:airasia" {...props}></Icon>
