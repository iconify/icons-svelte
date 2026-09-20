<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_p4ewb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="o_p4ewb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:library" {...props}></Icon>
