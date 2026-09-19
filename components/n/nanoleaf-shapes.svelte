<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy5p4lb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy5p4lb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-shapes" {...props}></Icon>
