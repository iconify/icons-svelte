<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdgq2lbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdgq2lbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heading-2-solid" {...props}></Icon>
