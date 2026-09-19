<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwsk7dcmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uwsk7dcmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:columns-outline" {...props}></Icon>
