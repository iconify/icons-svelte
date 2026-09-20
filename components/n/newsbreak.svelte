<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcb_4fb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcb_4fb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:newsbreak" {...props}></Icon>
