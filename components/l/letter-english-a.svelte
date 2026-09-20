<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_0stws9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_0stws9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:letter-english-a" {...props}></Icon>
