<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-h2gbb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-h2gbb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chromecast" {...props}></Icon>
