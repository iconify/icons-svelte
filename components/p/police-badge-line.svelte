<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqxqd7bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqxqd7bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:police-badge-line" {...props}></Icon>
