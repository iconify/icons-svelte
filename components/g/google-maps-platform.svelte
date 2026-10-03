<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjazihb8a.css';
import '../../css/b/bebqe1bxz.css';
import '../../css/u/ubukluesx.css';
import '../../css/u/u8jp0itvb.css';
import '../../css/q/qwrx_blcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjazihb8a"/><path class="bebqe1bxz"/><path class="ubukluesx"/><path class="u8jp0itvb"/><path class="qwrx_blcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:google-maps-platform" {...props}></Icon>
