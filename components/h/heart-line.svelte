<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac9g-cx8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac9g-cx8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-line" {...props}></Icon>
