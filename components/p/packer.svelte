<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ljfv5ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ljfv5ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:packer" {...props}></Icon>
