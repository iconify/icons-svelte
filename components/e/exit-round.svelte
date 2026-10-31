<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k59sddylk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k59sddylk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:exit-round" {...props}></Icon>
