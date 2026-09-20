<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdh-lqh4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xdh-lqh4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-perspective-outline" {...props}></Icon>
