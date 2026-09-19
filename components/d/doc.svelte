<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o62692bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":760,"height":1000};
const content = `<path class="o62692bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:doc" {...props}></Icon>
