<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxwfs3h9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxwfs3h9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:paddle" {...props}></Icon>
