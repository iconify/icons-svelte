<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfj4g962m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfj4g962m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-add-light" {...props}></Icon>
