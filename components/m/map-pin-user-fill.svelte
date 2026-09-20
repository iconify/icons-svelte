<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7apwdq2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7apwdq2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-user-fill" {...props}></Icon>
