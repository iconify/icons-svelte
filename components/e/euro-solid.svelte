<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogh1vxbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ogh1vxbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:euro-solid" {...props}></Icon>
