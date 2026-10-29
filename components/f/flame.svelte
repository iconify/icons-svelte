<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa_l6hbaj.css';
import '../../css/m/mylxy3b_v.css';
import '../../css/d/d8znebcca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k xa_l6hbaj"/><path class="mylxy3b_v wm-k"/><path class="d8znebcca wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:flame" {...props}></Icon>
