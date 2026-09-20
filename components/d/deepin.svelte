<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wffzy9rcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wffzy9rcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:deepin" {...props}></Icon>
