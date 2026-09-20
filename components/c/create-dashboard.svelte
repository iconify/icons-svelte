<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb-o2tbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb-o2tbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:create-dashboard" {...props}></Icon>
