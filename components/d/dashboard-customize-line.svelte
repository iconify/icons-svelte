<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdh68jixy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdh68jixy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dashboard-customize-line" {...props}></Icon>
