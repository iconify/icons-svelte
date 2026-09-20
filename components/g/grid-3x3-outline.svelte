<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/splw5nbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="splw5nbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-3x3-outline" {...props}></Icon>
