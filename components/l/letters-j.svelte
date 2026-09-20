<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxyqcybpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxyqcybpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-j" {...props}></Icon>
