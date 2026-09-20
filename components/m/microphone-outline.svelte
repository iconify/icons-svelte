<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcyfwob2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jcyfwob2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-outline" {...props}></Icon>
