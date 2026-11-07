<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo43we00a.css';
import '../../css/y/ytzb_u7ou.css';
import '../../css/c/c4946-17v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo43we00a"/><path class="ytzb_u7ou"/><path class="c4946-17v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-check-bold-duotone" {...props}></Icon>
