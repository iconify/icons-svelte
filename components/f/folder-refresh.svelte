<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft0cpxbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft0cpxbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-refresh" {...props}></Icon>
