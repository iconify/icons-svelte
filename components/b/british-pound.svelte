<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwseektoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwseektoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:british-pound" {...props}></Icon>
