<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd9lf2bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dd9lf2bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hospital-bold" {...props}></Icon>
