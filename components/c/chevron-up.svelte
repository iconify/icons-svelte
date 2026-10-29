<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h364t7brs.css';
import '../../css/i/i2z-fkbgx.css';
import '../../css/v/vbn0d_b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h364t7brs wm-shadow"/><path class="i2z-fkbgx wm-k"/><path class="vbn0d_b5k wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:chevron-up" {...props}></Icon>
