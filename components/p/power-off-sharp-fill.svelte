<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgi_pg35v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgi_pg35v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:power-off-sharp-fill" {...props}></Icon>
