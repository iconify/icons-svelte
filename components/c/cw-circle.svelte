<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntkigeb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ntkigeb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:cw-circle" {...props}></Icon>
