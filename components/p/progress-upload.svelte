<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er95ivb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er95ivb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:progress-upload" {...props}></Icon>
