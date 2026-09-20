<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg6y7tbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg6y7tbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bandsintown" {...props}></Icon>
