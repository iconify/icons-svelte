<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itw962baa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itw962baa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:craft-cms" {...props}></Icon>
