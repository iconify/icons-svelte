<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cea3snb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cea3snb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bitcomet" {...props}></Icon>
