<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ewjwd3r.css';
import '../../css/t/tmsq5rb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w5ewjwd3r"/><path class="primary tmsq5rb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:droplet-duo" {...props}></Icon>
