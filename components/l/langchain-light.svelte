<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tant6eb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":120};
const content = `<path class="tant6eb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:langchain-light" {...props}></Icon>
