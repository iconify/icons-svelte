<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i29sy8rki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i29sy8rki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-line" {...props}></Icon>
