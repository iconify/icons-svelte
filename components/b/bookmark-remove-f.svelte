<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5m-knbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="f5m-knbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bookmark-remove-f" {...props}></Icon>
