<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0hjt0kyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0hjt0kyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:corona-engine" {...props}></Icon>
