<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0f-scclc.css';
import '../../css/a/a-gh_pbjk.css';
import '../../css/m/me9tsg_kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0f-scclc"/><path class="a-gh_pbjk"/><circle class="me9tsg_kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-train" {...props}></Icon>
