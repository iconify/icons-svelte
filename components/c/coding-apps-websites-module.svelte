<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7b-ivwtn.css';
import '../../css/c/cn0ji2cwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f7b-ivwtn"/><path class="cn0ji2cwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-module" {...props}></Icon>
