<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aogk6ik8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aogk6ik8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:purgecss" {...props}></Icon>
