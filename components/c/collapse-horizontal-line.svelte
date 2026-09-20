<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5vnpthlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5vnpthlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:collapse-horizontal-line" {...props}></Icon>
