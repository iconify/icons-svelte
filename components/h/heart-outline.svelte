<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh4nw25wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vh4nw25wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-outline" {...props}></Icon>
