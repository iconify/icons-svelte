<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovno7d_nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovno7d_nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-tv" {...props}></Icon>
