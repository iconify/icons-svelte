<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4qg93bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4qg93bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-edit-outline" {...props}></Icon>
