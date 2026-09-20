<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs9p4d8nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs9p4d8nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ikea" {...props}></Icon>
