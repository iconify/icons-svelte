<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhgas6b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rhgas6b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fire-outline" {...props}></Icon>
