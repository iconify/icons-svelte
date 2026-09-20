<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1kw9kk6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1kw9kk6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-sync" {...props}></Icon>
