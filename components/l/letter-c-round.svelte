<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idinelqba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idinelqba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-c-round" {...props}></Icon>
