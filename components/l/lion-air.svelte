<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvqgtj7iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvqgtj7iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lion-air" {...props}></Icon>
