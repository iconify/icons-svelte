<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdexllbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdexllbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gitbook-line" {...props}></Icon>
