<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so21iw-ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so21iw-ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:knime" {...props}></Icon>
