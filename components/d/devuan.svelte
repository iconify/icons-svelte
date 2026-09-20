<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph48qgb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph48qgb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:devuan" {...props}></Icon>
