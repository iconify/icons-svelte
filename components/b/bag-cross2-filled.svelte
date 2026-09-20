<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si_qkgb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si_qkgb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-cross2-filled" {...props}></Icon>
