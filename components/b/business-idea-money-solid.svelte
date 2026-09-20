<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtief1bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qtief1bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:business-idea-money-solid" {...props}></Icon>
