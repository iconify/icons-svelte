<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd8wttb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8wttb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gumroad" {...props}></Icon>
