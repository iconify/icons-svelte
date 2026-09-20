<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw7o6gbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw7o6gbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ripple" {...props}></Icon>
