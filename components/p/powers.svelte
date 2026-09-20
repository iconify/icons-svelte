<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3cbu4bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3cbu4bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:powers" {...props}></Icon>
