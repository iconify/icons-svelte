<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3rimeb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3rimeb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:app-badge-outline" {...props}></Icon>
