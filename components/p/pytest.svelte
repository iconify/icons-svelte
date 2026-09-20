<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-ilh3bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ilh3bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pytest" {...props}></Icon>
