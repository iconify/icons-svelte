<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g76-_3dup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g76-_3dup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freebsd" {...props}></Icon>
