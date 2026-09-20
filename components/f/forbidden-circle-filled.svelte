<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he5vvvb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he5vvvb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forbidden-circle-filled" {...props}></Icon>
