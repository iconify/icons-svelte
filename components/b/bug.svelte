<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg5j54blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="fg5j54blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bug" {...props}></Icon>
