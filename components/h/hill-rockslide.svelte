<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk7_0uzhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="uk7_0uzhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hill-rockslide" {...props}></Icon>
