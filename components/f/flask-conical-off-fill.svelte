<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7fj0wb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7fj0wb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flask-conical-off-fill" {...props}></Icon>
