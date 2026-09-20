<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppq-09n2f.css';
import '../../css/l/l72h1vbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ppq-09n2f"/><path clip-rule="evenodd" class="l72h1vbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:doc-solid" {...props}></Icon>
