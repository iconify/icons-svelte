<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2qisrbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2qisrbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:motor-off-outline" {...props}></Icon>
