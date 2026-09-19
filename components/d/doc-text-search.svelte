<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idcy0_bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="idcy0_bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-text-search" {...props}></Icon>
