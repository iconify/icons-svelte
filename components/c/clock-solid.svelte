<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk_cstb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk_cstb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clock-solid" {...props}></Icon>
