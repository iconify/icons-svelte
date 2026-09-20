<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emac03b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="emac03b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-button-up-arrow-up-keyboard" {...props}></Icon>
