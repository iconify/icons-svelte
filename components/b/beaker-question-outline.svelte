<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7cs2_b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7cs2_b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:beaker-question-outline" {...props}></Icon>
