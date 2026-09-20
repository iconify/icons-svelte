<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8v7zs.css';
import '../../css/s/so-from-28.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8v7zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:paint-drop" {...props}></Icon>
