<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g77xi_7ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g77xi_7ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-wifi-remix" {...props}></Icon>
