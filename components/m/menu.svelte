<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgi_h6bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgi_h6bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:menu" {...props}></Icon>
