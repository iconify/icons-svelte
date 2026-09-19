<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d09-d0b7r.css';
import '../../css/l/l44o3se9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d09-d0b7r"/><path class="l44o3se9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ball-throw-filled" {...props}></Icon>
