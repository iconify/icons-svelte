<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu_ca8b3i.css';
import '../../css/r/r-h8u5bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu_ca8b3i"/><path class="r-h8u5bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:instagram-logo-bold" {...props}></Icon>
