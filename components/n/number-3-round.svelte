<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koc7tsbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koc7tsbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-3-round" {...props}></Icon>
