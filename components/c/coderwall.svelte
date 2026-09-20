<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvpp2bcjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvpp2bcjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:coderwall" {...props}></Icon>
