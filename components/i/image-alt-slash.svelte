<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_n-gduge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_n-gduge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-alt-slash" {...props}></Icon>
