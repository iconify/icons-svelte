<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og17uacas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="og17uacas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:organization-26" {...props}></Icon>
