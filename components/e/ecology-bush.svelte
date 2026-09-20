<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6pzp95xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s6pzp95xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-bush" {...props}></Icon>
