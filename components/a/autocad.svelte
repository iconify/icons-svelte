<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrdmtsb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrdmtsb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:autocad" {...props}></Icon>
