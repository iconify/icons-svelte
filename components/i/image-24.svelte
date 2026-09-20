<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scjro9brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scjro9brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:image-24" {...props}></Icon>
