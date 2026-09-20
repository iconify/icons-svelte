<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnqtm9qzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xnqtm9qzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:list-bulleted" {...props}></Icon>
