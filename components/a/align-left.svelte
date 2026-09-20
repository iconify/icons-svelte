<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfm2g-bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfm2g-bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-left" {...props}></Icon>
