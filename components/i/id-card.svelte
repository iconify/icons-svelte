<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx66pva8x.css';
import '../../css/z/z0pbxopjv.css';
import '../../css/n/ntgg6relj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx66pva8x wm-k"/><path class="wm-a z0pbxopjv"/><path class="ntgg6relj wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:id-card" {...props}></Icon>
