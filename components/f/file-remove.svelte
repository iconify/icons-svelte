<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxawnovcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxawnovcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-remove" {...props}></Icon>
