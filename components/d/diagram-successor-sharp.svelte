<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u37__bb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u37__bb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:diagram-successor-sharp" {...props}></Icon>
