<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3uwj83vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3uwj83vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-connect" {...props}></Icon>
