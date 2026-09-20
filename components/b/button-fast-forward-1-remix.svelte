<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izb-tjjqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="izb-tjjqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-fast-forward-1-remix" {...props}></Icon>
