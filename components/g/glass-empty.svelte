<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhr1w3b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="hhr1w3b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:glass-empty" {...props}></Icon>
