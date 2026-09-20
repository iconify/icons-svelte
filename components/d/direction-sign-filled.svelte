<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbva0sn3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbva0sn3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:direction-sign-filled" {...props}></Icon>
