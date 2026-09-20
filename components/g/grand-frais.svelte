<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-he2ybnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-he2ybnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:grand-frais" {...props}></Icon>
