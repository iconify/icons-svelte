<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op6a2bbfz.css';
import '../../css/s/s6z8b405g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op6a2bbfz"/><path class="s6z8b405g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:folder-open" {...props}></Icon>
