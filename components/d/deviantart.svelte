<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwkfe5ngs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwkfe5ngs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:deviantart" {...props}></Icon>
