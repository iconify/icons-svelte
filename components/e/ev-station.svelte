<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go4i3w7cb.css';
import '../../css/e/e12zghbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go4i3w7cb"/><path class="e12zghbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ev-station" {...props}></Icon>
