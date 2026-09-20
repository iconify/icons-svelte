<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa1gcpbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa1gcpbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-right-outline" {...props}></Icon>
