<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukgok--ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukgok--ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-add-line" {...props}></Icon>
