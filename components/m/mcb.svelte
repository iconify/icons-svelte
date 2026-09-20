<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfj9j6blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfj9j6blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mcb" {...props}></Icon>
