<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcno_eowz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcno_eowz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:headset-issue" {...props}></Icon>
