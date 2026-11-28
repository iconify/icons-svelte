<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghv0-2b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ghv0-2b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bring-to-front-bold" {...props}></Icon>
