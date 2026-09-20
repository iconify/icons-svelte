<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2b9ambve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2b9ambve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flag-off-fill" {...props}></Icon>
