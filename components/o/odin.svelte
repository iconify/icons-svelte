<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbt85wbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbt85wbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:odin" {...props}></Icon>
