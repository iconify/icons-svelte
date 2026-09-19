<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l74d4lbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l74d4lbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:menu-right-alt" {...props}></Icon>
