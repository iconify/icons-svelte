<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4-20mbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4-20mbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:perfume-outline" {...props}></Icon>
