<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me3btxa7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me3btxa7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:box-open" {...props}></Icon>
