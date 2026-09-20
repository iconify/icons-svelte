<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi4wy4h2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xi4wy4h2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:face-grinning-solid" {...props}></Icon>
