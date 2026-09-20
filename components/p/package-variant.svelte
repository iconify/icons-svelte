<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grh1jhbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grh1jhbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:package-variant" {...props}></Icon>
