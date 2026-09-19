<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz6yhgbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rz6yhgbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-on-square-stack-20-solid" {...props}></Icon>
