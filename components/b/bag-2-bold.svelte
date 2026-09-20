<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci88u-2xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ci88u-2xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-2-bold" {...props}></Icon>
