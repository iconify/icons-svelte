<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y72vournz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y72vournz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cloud-data-transfer-remix" {...props}></Icon>
