<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox9k-ul3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox9k-ul3r primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:baseline-shift-duotone" {...props}></Icon>
