<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv43l2zsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv43l2zsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:frappe" {...props}></Icon>
