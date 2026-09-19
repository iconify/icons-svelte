<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv059fbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv059fbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-circle-down-fill" {...props}></Icon>
