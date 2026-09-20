<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s23tf7rzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s23tf7rzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:devbox" {...props}></Icon>
