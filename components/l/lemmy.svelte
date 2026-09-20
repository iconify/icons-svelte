<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxyn5kb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxyn5kb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lemmy" {...props}></Icon>
