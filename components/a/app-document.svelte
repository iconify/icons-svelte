<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg4ufqbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sg4ufqbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:app-document" {...props}></Icon>
