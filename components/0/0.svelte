<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcztpib1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="tcztpib1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:0" {...props}></Icon>
