<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyzuu4cmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyzuu4cmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reel-outline" {...props}></Icon>
