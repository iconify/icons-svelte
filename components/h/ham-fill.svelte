<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lab7x-wem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lab7x-wem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ham-fill" {...props}></Icon>
