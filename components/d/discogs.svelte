<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as8xgsb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as8xgsb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:discogs" {...props}></Icon>
