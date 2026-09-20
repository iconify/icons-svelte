<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d92pih7bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d92pih7bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-30-fill" {...props}></Icon>
