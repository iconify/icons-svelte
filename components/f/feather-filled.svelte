<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxn65k2kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxn65k2kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:feather-filled" {...props}></Icon>
