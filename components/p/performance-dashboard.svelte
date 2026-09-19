<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0ee3cbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0ee3cbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:performance-dashboard" {...props}></Icon>
