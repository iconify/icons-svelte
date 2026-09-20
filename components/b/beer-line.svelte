<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9tnc6n-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9tnc6n-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:beer-line" {...props}></Icon>
