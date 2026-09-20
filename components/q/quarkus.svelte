<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grr8c5bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grr8c5bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quarkus" {...props}></Icon>
