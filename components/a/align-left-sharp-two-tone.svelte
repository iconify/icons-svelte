<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8idp9_5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8idp9_5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-left-sharp-two-tone" {...props}></Icon>
