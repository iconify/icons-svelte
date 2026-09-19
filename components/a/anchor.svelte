<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud1alzb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":32};
const content = `<path class="ud1alzb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:anchor" {...props}></Icon>
