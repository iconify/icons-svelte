<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut_yg9bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut_yg9bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-open-two-tone" {...props}></Icon>
