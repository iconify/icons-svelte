<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcdi9wggu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcdi9wggu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rossmann" {...props}></Icon>
