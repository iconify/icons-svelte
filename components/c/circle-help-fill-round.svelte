<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp30w0h8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp30w0h8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-help-fill-round" {...props}></Icon>
