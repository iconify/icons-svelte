<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff5ivpbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff5ivpbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cweb" {...props}></Icon>
