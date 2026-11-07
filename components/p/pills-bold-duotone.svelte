<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9h5fmbqx.css';
import '../../css/h/hsjczmubo.css';
import '../../css/x/x5yc8ybio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9h5fmbqx"/><path class="hsjczmubo"/><path class="x5yc8ybio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pills-bold-duotone" {...props}></Icon>
