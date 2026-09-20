<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqjko4y1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="tqjko4y1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:instant-picture-f" {...props}></Icon>
