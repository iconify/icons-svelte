<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbrjd2beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mbrjd2beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:jug-detergent" {...props}></Icon>
