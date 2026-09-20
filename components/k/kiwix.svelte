<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnd8lgb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnd8lgb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kiwix" {...props}></Icon>
