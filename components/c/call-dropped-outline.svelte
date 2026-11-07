<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2_o7ybby.css';
import '../../css/y/yq6674bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2_o7ybby"/><path class="yq6674bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-dropped-outline" {...props}></Icon>
