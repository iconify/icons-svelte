<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiz4ovnxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiz4ovnxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:color-fill" {...props}></Icon>
