<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsqcs4bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsqcs4bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:globe-lock" {...props}></Icon>
