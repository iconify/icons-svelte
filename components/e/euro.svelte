<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0nlblb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="v0nlblb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:euro" {...props}></Icon>
