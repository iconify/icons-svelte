<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e09p27jqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e09p27jqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nextflow" {...props}></Icon>
