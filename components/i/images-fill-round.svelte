<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmxb9zfvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmxb9zfvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:images-fill-round" {...props}></Icon>
