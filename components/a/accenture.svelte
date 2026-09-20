<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-e6l2b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-e6l2b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:accenture" {...props}></Icon>
