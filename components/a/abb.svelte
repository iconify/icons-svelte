<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uagzrrb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uagzrrb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:abb" {...props}></Icon>
