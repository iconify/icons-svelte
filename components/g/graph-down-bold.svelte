<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o53rsb-vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o53rsb-vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-down-bold" {...props}></Icon>
