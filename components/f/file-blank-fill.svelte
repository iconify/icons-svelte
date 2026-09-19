<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtu8q4byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtu8q4byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-blank-fill" {...props}></Icon>
