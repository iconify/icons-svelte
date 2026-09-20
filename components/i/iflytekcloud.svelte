<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f28nl8btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f28nl8btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:iflytekcloud" {...props}></Icon>
