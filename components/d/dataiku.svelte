<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4_zh6b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4_zh6b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dataiku" {...props}></Icon>
