<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzbunwi2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzbunwi2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:k6" {...props}></Icon>
