<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzmyd9baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yzmyd9baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lodgify" {...props}></Icon>
