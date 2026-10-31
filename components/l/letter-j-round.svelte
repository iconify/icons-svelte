<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjb9cvb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjb9cvb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-j-round" {...props}></Icon>
