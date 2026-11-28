<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i86-ptzrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i86-ptzrh primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:colon-duotone" {...props}></Icon>
