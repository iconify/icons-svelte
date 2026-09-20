<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlj__gane.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlj__gane"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-e-filled" {...props}></Icon>
