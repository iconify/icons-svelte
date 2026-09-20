<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk9escb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk9escb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diamond-2-fill" {...props}></Icon>
