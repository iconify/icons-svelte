<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geu0kot6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geu0kot6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nhost" {...props}></Icon>
