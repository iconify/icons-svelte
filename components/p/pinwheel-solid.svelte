<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6ark1bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i6ark1bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pinwheel-solid" {...props}></Icon>
