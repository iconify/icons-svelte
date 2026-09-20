<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbk4adc7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbk4adc7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-data-conversion-documents-1" {...props}></Icon>
