<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2o7z2uqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2o7z2uqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-3-square-light" {...props}></Icon>
