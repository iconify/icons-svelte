<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhd7pyo3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhd7pyo3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-snooze-solid" {...props}></Icon>
