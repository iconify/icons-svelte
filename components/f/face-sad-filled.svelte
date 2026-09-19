<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b85_wvb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b85_wvb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:face-sad-filled" {...props}></Icon>
