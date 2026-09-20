<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_7prvx0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_7prvx0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:explore-filled" {...props}></Icon>
