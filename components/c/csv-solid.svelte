<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_1fj88zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="p_1fj88zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:csv-solid" {...props}></Icon>
