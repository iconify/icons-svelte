<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gufejb2cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="gufejb2cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:note" {...props}></Icon>
