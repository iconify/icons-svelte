<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw3neacco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw3neacco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-text-lock" {...props}></Icon>
