<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-7ndvbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-7ndvbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-3x3-bold" {...props}></Icon>
