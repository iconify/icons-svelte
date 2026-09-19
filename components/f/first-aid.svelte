<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okyebdcgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okyebdcgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:first-aid" {...props}></Icon>
