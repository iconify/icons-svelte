<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcpbjebll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcpbjebll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:apple-fill" {...props}></Icon>
