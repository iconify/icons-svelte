<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0cbgc7ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0cbgc7ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:option" {...props}></Icon>
