<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whoue71nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whoue71nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:birthday-2-line" {...props}></Icon>
