<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5dk1gb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5dk1gb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:creative-commons" {...props}></Icon>
