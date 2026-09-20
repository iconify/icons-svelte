<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb3nn5obp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb3nn5obp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-wrap-tight" {...props}></Icon>
