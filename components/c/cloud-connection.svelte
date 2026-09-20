<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nypu68bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nypu68bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-connection" {...props}></Icon>
