<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv55pk_2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv55pk_2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:deluge" {...props}></Icon>
