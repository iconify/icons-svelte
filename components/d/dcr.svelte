<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scih79b8c.css';
import '../../css/m/me4-nbcbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scih79b8c"/><path class="me4-nbcbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dcr" {...props}></Icon>
