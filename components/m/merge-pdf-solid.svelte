<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knrd91d8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="knrd91d8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:merge-pdf-solid" {...props}></Icon>
