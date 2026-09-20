<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgd2rnb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgd2rnb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:renren" {...props}></Icon>
