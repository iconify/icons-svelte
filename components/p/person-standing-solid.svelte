<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpuo92byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpuo92byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:person-standing-solid" {...props}></Icon>
