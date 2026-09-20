<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udjd-0bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="udjd-0bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:hierarchy-line-3-solid" {...props}></Icon>
