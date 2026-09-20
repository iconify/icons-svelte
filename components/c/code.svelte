<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w061shbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w061shbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:code" {...props}></Icon>
