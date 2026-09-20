<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1a73l0-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1a73l0-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:laptop" {...props}></Icon>
