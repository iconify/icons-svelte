<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eahhbjbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eahhbjbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bluetooth-outline" {...props}></Icon>
