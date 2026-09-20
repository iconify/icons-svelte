<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5g7e_k4u.css';
import '../../css/m/mob_cyb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5g7e_k4u"/><path clip-rule="evenodd" class="mob_cyb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-stop-fill" {...props}></Icon>
