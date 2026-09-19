<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qus7vzb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qus7vzb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-arrow-down-20-solid" {...props}></Icon>
