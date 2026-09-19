<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2gfdcblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2gfdcblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-expand" {...props}></Icon>
