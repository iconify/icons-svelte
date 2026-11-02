<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m400souyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m400souyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-check-fill" {...props}></Icon>
