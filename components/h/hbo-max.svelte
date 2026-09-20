<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zupls5bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zupls5bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hbo-max" {...props}></Icon>
