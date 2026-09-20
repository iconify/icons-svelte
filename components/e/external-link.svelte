<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4amp7bme.css';
import '../../css/n/nnh_4z2za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4amp7bme"/><path class="nnh_4z2za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:external-link" {...props}></Icon>
