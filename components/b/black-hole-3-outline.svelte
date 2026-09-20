<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocx9c_b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocx9c_b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:black-hole-3-outline" {...props}></Icon>
