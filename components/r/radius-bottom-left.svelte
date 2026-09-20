<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfx6rsbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfx6rsbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:radius-bottom-left" {...props}></Icon>
