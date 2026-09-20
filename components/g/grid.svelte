<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2i6f7o9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2i6f7o9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:grid" {...props}></Icon>
