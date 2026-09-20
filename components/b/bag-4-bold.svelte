<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or1gdwb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="or1gdwb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-4-bold" {...props}></Icon>
