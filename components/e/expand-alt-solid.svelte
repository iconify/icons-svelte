<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz_vj9-yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jz_vj9-yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:expand-alt-solid" {...props}></Icon>
