<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smvh7b4ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smvh7b4ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ferrari-ndotvdot" {...props}></Icon>
