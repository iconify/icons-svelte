<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4ikh4a_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4ikh4a_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:repeat-once-solid" {...props}></Icon>
