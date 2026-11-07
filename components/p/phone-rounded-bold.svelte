<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwtl__1sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwtl__1sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-rounded-bold" {...props}></Icon>
