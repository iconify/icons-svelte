<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgc_t5b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgc_t5b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:at" {...props}></Icon>
