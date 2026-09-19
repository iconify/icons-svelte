<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alc589sng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="alc589sng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-goggles-24px" {...props}></Icon>
