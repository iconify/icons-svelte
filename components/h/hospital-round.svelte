<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzlw3mbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzlw3mbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hospital-round" {...props}></Icon>
