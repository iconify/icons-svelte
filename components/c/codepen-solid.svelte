<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op9xqsb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="op9xqsb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:codepen-solid" {...props}></Icon>
