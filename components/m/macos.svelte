<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_wx9sbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_wx9sbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:macos" {...props}></Icon>
