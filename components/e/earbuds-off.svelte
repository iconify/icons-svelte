<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y51rkfblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y51rkfblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:earbuds-off" {...props}></Icon>
