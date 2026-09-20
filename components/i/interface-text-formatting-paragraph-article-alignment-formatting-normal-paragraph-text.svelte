<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si2ppcpkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="si2ppcpkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-paragraph-article-alignment-formatting-normal-paragraph-text" {...props}></Icon>
