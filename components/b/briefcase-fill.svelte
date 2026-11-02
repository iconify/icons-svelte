<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnr7gmnxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnr7gmnxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:briefcase-fill" {...props}></Icon>
