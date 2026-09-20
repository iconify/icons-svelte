<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3xv7-bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3xv7-bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fido-alliance" {...props}></Icon>
