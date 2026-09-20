<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf0pdw_6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf0pdw_6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bell-fill-24" {...props}></Icon>
