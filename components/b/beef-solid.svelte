<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o91i2d-pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o91i2d-pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:beef-solid" {...props}></Icon>
