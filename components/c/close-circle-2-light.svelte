<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-zho3bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-zho3bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-circle-2-light" {...props}></Icon>
