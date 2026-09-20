<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc64kfbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pc64kfbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:presentation" {...props}></Icon>
