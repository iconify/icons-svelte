<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i22riebbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i22riebbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:fahrenheit" {...props}></Icon>
