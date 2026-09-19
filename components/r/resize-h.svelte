<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noys57btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="noys57btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:resize-h" {...props}></Icon>
