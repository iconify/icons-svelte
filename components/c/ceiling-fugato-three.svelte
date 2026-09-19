<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-s1xmbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-s1xmbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-fugato-three" {...props}></Icon>
