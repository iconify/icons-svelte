<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tly34rbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tly34rbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-full-round" {...props}></Icon>
