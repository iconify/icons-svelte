<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suwu-_bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suwu-_bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:departure" {...props}></Icon>
