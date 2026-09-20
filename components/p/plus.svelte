<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvqgy2b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvqgy2b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:plus" {...props}></Icon>
