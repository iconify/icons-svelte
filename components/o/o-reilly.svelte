<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1oxaw98x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1oxaw98x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:o-reilly" {...props}></Icon>
