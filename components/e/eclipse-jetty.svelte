<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt0xxlb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt0xxlb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:eclipse-jetty" {...props}></Icon>
