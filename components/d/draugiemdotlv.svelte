<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j34peacel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j34peacel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:draugiemdotlv" {...props}></Icon>
