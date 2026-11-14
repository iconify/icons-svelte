<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaej_g74q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaej_g74q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:login-02" {...props}></Icon>
