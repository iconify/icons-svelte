<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnjif5a_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnjif5a_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:folder-outline" {...props}></Icon>
