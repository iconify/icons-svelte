<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-kfp_d1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="a-kfp_d1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:add-solid" {...props}></Icon>
