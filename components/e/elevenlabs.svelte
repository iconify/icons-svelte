<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah0tzibwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah0tzibwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:elevenlabs" {...props}></Icon>
