<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbo-p0bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbo-p0bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:linuxfoundation" {...props}></Icon>
