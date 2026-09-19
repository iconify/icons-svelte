<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8e1r5b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8e1r5b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:heart-off-fill" {...props}></Icon>
