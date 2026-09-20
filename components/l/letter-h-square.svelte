<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wltyzmbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wltyzmbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-h-square" {...props}></Icon>
