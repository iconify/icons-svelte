<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7fxx3b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7fxx3b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:film" {...props}></Icon>
