<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as4xm9byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as4xm9byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:apps-2-fill" {...props}></Icon>
