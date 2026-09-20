<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqlkaybxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqlkaybxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hedgedoc" {...props}></Icon>
