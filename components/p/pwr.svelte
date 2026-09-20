<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcoh9zb5r.css';
import '../../css/b/bve8ubjqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcoh9zb5r"/><path class="bve8ubjqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pwr" {...props}></Icon>
