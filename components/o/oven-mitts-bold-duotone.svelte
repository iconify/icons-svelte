<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y63wv5bum.css';
import '../../css/a/a-ssoobaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y63wv5bum"/><path class="a-ssoobaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:oven-mitts-bold-duotone" {...props}></Icon>
