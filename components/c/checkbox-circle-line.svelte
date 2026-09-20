<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx4n7nbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx4n7nbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-circle-line" {...props}></Icon>
