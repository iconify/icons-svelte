<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dggly8hlh.css';
import '../../css/r/r1dxseh_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dggly8hlh"/><path class="r1dxseh_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:comments-solid" {...props}></Icon>
