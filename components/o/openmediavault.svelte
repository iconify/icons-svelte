<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3woy32xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3woy32xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:openmediavault" {...props}></Icon>
