<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa9s_vb_p.css';
import '../../css/m/mh82_cb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer sa9s_vb_p"/><path class="duoicon-primary-layer mh82_cb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:award" {...props}></Icon>
