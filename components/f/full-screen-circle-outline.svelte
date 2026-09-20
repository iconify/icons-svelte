<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v49232f_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v49232f_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-circle-outline" {...props}></Icon>
