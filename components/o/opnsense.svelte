<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1o7eg5_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1o7eg5_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opnsense" {...props}></Icon>
