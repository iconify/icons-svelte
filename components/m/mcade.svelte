<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6s6452ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6s6452ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mcade" {...props}></Icon>
