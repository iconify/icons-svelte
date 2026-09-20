<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzd-2m8yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzd-2m8yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-fill" {...props}></Icon>
