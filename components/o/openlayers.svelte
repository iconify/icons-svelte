<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt5086bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt5086bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openlayers" {...props}></Icon>
