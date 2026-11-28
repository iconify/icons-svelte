<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re1y-rbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re1y-rbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:butterfly-solid" {...props}></Icon>
