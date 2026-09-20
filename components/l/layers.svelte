<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-oz6hbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-4};
const content = `<path class="p-oz6hbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:layers" {...props}></Icon>
