<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vundi_b1g.css';
import '../../css/z/zqqdl4nxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vundi_b1g"/><path class="zqqdl4nxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:navigate-duotone" {...props}></Icon>
